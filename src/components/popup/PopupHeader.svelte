<script lang="ts">
    import getManifest from "../../utils/getManifest";

    const version = getManifest().version;
</script>

<div class="header">
    <span>AI TEXT DETECTOR v{version}</span>
</div>

<style>
    .header {
        border-bottom: 1px solid rgba(0,0,0,.06);
        height: 46px;
        color: #15c39a;
        display: flex;
        align-items: center;
        justify-content: center;
        font-style: normal;
        font-weight: 700;
        font-size: 14px;
        color: rgb(14, 16, 26);
    }
</style>
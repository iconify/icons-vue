<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8spygx2w.css';
import '../../css/r/rjrkgcc1w.css';
import '../../css/l/lxpqrmtxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a8spygx2w"/><path class="rjrkgcc1w"/><path class="lxpqrmtxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:worm-gear-48-bold" /></template>

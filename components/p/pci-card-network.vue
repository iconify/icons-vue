<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c77bytqov.css';
import '../../css/b/bvn-2db2g.css';
import '../../css/d/dvlkv87yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="c77bytqov"/><path class="bvn-2db2g"/><path class="dvlkv87yt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pci-card-network" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vkwwp42am.css';
import '../../css/b/bw4rmmbty.css';
import '../../css/n/nyyahnbxx.css';
import '../../css/b/byu9zgdxu.css';
import '../../css/e/eonjggvry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vkwwp42am"/><path class="bw4rmmbty"/><path class="nyyahnbxx"/><circle class="byu9zgdxu"/><path class="eonjggvry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-by-time-linear" /></template>

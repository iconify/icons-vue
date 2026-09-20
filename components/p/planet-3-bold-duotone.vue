<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y9e2kcbuv.css';
import '../../css/k/k774yynor.css';
import '../../css/d/dnka95bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y9e2kcbuv"/><path class="k774yynor"/><path class="dnka95bah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-3-bold-duotone" /></template>

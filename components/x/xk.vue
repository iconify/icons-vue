<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aui1ykh8i.css';
import '../../css/z/zumbbfb7g.css';
import '../../css/n/nobw7knev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":200};
const content = `<g class="ft5dv1b6b"><path class="aui1ykh8i"/><path class="zumbbfb7g"/><path class="nobw7knev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:xk" /></template>

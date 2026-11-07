<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zu6ek4h1t.css';
import '../../css/r/rgbhf6bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":77};
const content = `<g class="cuyn6tgcc"><path class="zu6ek4h1t"/><path class="rgbhf6bcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:warden" /></template>

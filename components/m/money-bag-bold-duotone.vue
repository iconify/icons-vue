<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c38jz1bub.css';
import '../../css/b/b3gp8zbvg.css';
import '../../css/w/wqsjcy92r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c38jz1bub"/><path class="b3gp8zbvg"/><path class="wqsjcy92r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:money-bag-bold-duotone" /></template>

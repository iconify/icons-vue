<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dvzi3lbpc.css';
import '../../css/z/zfoh0m8an.css';
import '../../css/p/ps9o2abca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dvzi3lbpc"/><path class="zfoh0m8an"/><path class="ps9o2abca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:suitcase-2-filled" /></template>

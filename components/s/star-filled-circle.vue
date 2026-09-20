<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cdbpfnb7d.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="cdbpfnb7d"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:star-filled-circle" /></template>

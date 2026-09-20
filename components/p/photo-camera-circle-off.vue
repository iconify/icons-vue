<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/itpmqb1vd.css';
import '../../css/l/lztqcuc6i.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="itpmqb1vd"/><path clip-rule="evenodd" class="lztqcuc6i"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:photo-camera-circle-off" /></template>

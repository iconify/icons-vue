<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nph3bgbre.css';
import '../../css/g/gerr7wbkt.css';
import '../../css/q/qrpq7hb7i.css';
import '../../css/j/jri1llz4a.css';
import '../../css/b/bf0ij55fy.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/x/xnamy9b0v.css';
import '../../css/u/uqxc142gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="nph3bgbre"/><path class="gerr7wbkt"/><path class="qrpq7hb7i"/><path class="jri1llz4a"/><path class="bf0ij55fy"/><g class="jn8qy4bru"><path class="xnamy9b0v"/><path class="uqxc142gd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:warning-strip-right" /></template>

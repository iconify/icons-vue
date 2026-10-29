<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/dlemphk8j.css';
import '../../css/i/i76dh14xw.css';
import '../../css/g/gj0zhrbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="dlemphk8j"/><path class="i76dh14xw"/><path class="gj0zhrbiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:rectangle-ellipsis" /></template>

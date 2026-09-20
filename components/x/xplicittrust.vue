<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvg_0h2iy.css';
import '../../css/b/b8e-k_44m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xvg_0h2iy"/><path class="b8e-k_44m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xplicittrust" /></template>

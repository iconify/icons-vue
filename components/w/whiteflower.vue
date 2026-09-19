<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1oj3o3gm.css';
import '../../css/h/hy2vl0dwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n1oj3o3gm"/><path class="hy2vl0dwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whiteflower" /></template>

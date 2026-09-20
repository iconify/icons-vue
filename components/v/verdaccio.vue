<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrsdmp1_y.css';
import '../../css/t/tjg9g-oad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xrsdmp1_y"/><path class="tjg9g-oad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:verdaccio" /></template>

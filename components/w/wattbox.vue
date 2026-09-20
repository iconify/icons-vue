<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfc-29bll.css';
import '../../css/x/x_p186bjn.css';
import '../../css/a/a0c8erb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kfc-29bll"/><path class="x_p186bjn"/><path class="a0c8erb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wattbox" /></template>

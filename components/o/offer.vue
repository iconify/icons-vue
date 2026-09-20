<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izysojbwc.css';
import '../../css/v/vgcsy2b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="izysojbwc"/><path class="vgcsy2b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:offer" /></template>

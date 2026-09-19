<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooipf_b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ooipf_b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:vimeo-rect" /></template>

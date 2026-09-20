<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5ja4vb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m5ja4vb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:upload-3" /></template>

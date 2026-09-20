<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im2wm0ppx.css';
import '../../css/o/oi_6x_b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im2wm0ppx"/><path class="oi_6x_b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:trash-3" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by49boidr.css';
import '../../css/n/n96kk3b4d.css';
import '../../css/c/cxn0apbqq.css';
import '../../css/v/v3s8c5bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by49boidr"/><path class="n96kk3b4d"/><path class="cxn0apbqq"/><path class="v3s8c5bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:screencast-outline" /></template>

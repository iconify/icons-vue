<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf_0l2bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf_0l2bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pause-fill" /></template>

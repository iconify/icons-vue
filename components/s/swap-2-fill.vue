<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5xmveh_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5xmveh_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:swap-2-fill" /></template>

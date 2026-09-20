<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2l6e6b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2l6e6b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:zoom-in-fill" /></template>

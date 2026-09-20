<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj_w8biqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj_w8biqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:php-fill" /></template>

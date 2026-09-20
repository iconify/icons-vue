<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky2yuqb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky2yuqb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:zoom-out-line" /></template>

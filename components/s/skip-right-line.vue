<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec7eydbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec7eydbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:skip-right-line" /></template>

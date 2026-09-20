<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-w1fivvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-w1fivvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:restaurant-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exv8mvnqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exv8mvnqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:webhook-line" /></template>

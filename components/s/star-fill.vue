<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly-x4abvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly-x4abvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:star-fill" /></template>

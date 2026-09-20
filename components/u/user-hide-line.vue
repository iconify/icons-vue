<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kautov5ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kautov5ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-hide-line" /></template>

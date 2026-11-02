<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaw8b26al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaw8b26al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-square-10-line" /></template>

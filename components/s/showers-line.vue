<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-om3ebjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-om3ebjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:showers-line" /></template>

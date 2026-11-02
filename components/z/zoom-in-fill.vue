<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx7s3ezkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx7s3ezkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:zoom-in-fill" /></template>

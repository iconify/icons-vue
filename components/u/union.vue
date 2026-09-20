<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb8khkb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb8khkb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:union" /></template>

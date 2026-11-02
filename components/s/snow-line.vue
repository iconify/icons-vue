<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk9j6c3hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk9j6c3hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snow-line" /></template>

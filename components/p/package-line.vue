<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoh8w0bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoh8w0bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:package-line" /></template>

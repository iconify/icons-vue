<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snce60dbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snce60dbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:multiselect-line" /></template>

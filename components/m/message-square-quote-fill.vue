<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ces77_bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ces77_bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-quote-fill" /></template>

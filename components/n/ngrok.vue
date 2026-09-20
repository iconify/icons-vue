<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyv60mbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyv60mbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ngrok" /></template>

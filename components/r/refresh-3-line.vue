<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfihnpzmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfihnpzmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-3-line" /></template>

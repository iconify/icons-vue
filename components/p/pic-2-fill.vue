<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn1dswbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn1dswbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pic-2-fill" /></template>

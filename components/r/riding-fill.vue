<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de39s79xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de39s79xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:riding-fill" /></template>

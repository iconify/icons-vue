<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7k-ahbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7k-ahbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:star-half" /></template>

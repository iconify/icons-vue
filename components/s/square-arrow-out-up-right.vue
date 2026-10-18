<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tidhu8h8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tidhu8h8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-arrow-out-up-right" /></template>

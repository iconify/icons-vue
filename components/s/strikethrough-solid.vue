<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-b07z5rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-b07z5rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:strikethrough-solid" /></template>

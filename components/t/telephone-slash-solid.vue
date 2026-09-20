<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6ls90bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6ls90bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:telephone-slash-solid" /></template>

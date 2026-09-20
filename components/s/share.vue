<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbj5q2eai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbj5q2eai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:share" /></template>

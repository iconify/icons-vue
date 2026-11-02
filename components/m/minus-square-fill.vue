<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8b5skbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8b5skbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:minus-square-fill" /></template>

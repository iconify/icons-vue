<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikovoej2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikovoej2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:martini" /></template>

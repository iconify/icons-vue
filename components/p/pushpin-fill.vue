<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra6alvb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra6alvb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pushpin-fill" /></template>

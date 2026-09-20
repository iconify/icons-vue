<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc834ogky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc834ogky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pencil-line" /></template>

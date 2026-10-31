<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6owmcbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6owmcbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:moon-star-round" /></template>

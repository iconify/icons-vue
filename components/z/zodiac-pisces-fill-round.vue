<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utk1-nb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utk1-nb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-pisces-fill-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9xtl1ttf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9xtl1ttf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-missed-fill-round" /></template>

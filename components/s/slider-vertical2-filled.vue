<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xja7l4brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xja7l4brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:slider-vertical2-filled" /></template>

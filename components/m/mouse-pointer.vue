<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msie0p5ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msie0p5ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:mouse-pointer" /></template>

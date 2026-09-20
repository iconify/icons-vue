<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9ga-2bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9ga-2bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mouse-pointer" /></template>

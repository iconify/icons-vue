<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtb3trzmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtb3trzmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:zoom-in" /></template>

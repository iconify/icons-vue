<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl16xx4ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl16xx4ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-rotate-landscape" /></template>

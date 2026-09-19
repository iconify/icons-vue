<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbcehbbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbcehbbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:wine-glass" /></template>

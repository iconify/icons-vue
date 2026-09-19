<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ongrhhbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ongrhhbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:variable" /></template>

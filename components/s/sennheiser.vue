<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h42isz-5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h42isz-5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sennheiser" /></template>

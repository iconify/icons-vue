<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2ep2ccux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2ep2ccux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:user-minus" /></template>

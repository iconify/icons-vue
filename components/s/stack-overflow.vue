<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg6puob4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="fg6puob4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:stack-overflow" /></template>

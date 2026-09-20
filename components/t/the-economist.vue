<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx4b6zb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":250,"height":127.556};
const content = `<path class="wx4b6zb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:the-economist" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plpzo5o4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="plpzo5o4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:twitter-square" /></template>

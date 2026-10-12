<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz9el0b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yz9el0b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:star-fill-20" /></template>

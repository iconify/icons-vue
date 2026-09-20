<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-fl9ri0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n-fl9ri0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:star-o" /></template>

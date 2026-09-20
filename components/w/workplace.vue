<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg7hr-nny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wg7hr-nny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:workplace" /></template>

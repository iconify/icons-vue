<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0bc9uw-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v0bc9uw-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:strikethrough" /></template>

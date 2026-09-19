<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po68ny4my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="po68ny4my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:on-holiday-solid" /></template>

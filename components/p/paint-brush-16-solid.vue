<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ark4w8oht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ark4w8oht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:paint-brush-16-solid" /></template>

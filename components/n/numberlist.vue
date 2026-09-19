<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8y1soyur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z8y1soyur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:numberlist" /></template>

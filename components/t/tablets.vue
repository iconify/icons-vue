<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy84kabif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zy84kabif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tablets" /></template>

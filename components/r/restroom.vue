<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g208nobwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g208nobwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:restroom" /></template>

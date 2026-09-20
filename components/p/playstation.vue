<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syh5dib2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="syh5dib2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:playstation" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fted46bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fted46bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:studiovinari" /></template>

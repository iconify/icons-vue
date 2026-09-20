<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgid5pwjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vgid5pwjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:shopping-shipping-upload-information" /></template>

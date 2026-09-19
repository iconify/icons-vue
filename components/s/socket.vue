<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak-sz5dbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ak-sz5dbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:socket" /></template>

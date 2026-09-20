<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6yhfub-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d6yhfub-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:toilet-solid" /></template>

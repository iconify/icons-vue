<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez9oioo_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ez9oioo_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tram" /></template>

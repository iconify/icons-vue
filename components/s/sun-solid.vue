<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlgq87u_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nlgq87u_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sun-solid" /></template>

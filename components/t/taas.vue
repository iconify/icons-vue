<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enxacl_1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="enxacl_1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:taas" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgx7qua1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mgx7qua1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:networking" /></template>

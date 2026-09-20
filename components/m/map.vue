<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj6sv5lgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kj6sv5lgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:map" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu6zpr5jr.css';
import '../../css/c/czaquksml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zu6zpr5jr"/><path class="czaquksml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:receipt-sharp" /></template>

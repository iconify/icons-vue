<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwimcqx0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kwimcqx0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:trophy-filled" /></template>

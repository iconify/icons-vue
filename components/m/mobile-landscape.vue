<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf7pp8qih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qf7pp8qih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mobile-landscape" /></template>

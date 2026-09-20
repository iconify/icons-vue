<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8pcgvm3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g8pcgvm3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:walking" /></template>

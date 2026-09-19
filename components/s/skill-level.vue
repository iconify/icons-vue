<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwxcyee5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kwxcyee5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:skill-level" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm7z24m1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rm7z24m1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:truck" /></template>

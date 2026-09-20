<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqsabwbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lqsabwbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mobile-phone-with-touchscreen-and-antenna-and-bolt" /></template>

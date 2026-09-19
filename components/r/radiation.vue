<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe9q7uw-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fe9q7uw-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:radiation" /></template>

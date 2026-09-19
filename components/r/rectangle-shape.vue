<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esrx3jwdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="esrx3jwdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:rectangle-shape" /></template>

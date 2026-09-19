<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr40wtbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":208,"height":456};
const content = `<path class="tr40wtbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:right" /></template>

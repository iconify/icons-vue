<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvm3nfb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vvm3nfb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:oil-can" /></template>

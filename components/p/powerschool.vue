<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8h1w9rih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s8h1w9rih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:powerschool" /></template>

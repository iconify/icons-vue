<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4-bzk02u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="l4-bzk02u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:telephone-14" /></template>

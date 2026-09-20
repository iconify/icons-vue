<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3i8h8b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p3i8h8b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:rectangle-3" /></template>

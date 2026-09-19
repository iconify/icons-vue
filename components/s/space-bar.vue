<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykrxfx-4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="ykrxfx-4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:space-bar" /></template>

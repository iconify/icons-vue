<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugxa7f5cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="ugxa7f5cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:traffic" /></template>

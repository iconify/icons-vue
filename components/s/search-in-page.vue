<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxok0n99r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="cxok0n99r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:search-in-page" /></template>

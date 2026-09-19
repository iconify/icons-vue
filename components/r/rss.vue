<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxaqqbb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="pxaqqbb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:rss" /></template>

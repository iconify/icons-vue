<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io_j9j8zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="io_j9j8zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:razer" /></template>

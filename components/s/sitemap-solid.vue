<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj3mlhcrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mj3mlhcrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sitemap-solid" /></template>

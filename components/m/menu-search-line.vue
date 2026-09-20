<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqie0rbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqie0rbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:menu-search-line" /></template>

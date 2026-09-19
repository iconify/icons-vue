<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqhu8rbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":336,"height":432};
const content = `<path class="uqhu8rbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:stackoverflow" /></template>

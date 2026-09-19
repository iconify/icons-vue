<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oetz6qqlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="oetz6qqlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:replay" /></template>

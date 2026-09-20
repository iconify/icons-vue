<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3olkdzdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f3olkdzdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:mark-1" /></template>

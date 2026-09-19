<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc95llbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fc95llbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:sticky-note" /></template>

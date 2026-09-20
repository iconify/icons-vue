<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdkghbc_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fdkghbc_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:movie-filled" /></template>

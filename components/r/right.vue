<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6-exhbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":475,"height":717};
const content = `<path class="n6-exhbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:right" /></template>

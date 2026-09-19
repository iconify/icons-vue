<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4k767w9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="y4k767w9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:rev" /></template>

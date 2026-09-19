<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3vqukblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f3vqukblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:sitepoint" /></template>

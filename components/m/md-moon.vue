<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3v9z9dcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w3v9z9dcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-moon" /></template>

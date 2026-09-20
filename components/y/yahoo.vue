<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y679yacxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y679yacxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:yahoo" /></template>

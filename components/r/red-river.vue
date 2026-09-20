<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygsx_6hjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ygsx_6hjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:red-river" /></template>

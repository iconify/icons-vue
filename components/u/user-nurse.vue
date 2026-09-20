<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1zfrcc8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z1zfrcc8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-nurse" /></template>

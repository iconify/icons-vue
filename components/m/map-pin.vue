<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9p0trbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i9p0trbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:map-pin" /></template>

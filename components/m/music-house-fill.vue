<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg7u04blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vg7u04blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:music-house-fill" /></template>

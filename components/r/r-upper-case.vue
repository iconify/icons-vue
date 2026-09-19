<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u773yiv4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="u773yiv4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:r-upper-case" /></template>

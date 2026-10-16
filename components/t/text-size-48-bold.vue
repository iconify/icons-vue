<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjny1bchv.css';
import '../../css/x/xpq7hmt-u.css';
import '../../css/x/xyw2m9brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fjny1bchv"/><path class="xpq7hmt-u"/><path class="xyw2m9brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-size-48-bold" /></template>

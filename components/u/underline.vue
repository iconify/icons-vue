<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsjr3bb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jsjr3bb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:underline" /></template>

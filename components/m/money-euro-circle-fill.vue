<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f00vbwb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="f00vbwb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:money-euro-circle-fill" /></template>

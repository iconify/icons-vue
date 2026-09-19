<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te9cf7zxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="te9cf7zxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sheep" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbcik9bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="vbcik9bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:x-ray" /></template>

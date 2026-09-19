<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-06l_p3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":353,"height":512};
const content = `<path class="d-06l_p3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:rexx" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zljz0d6td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zljz0d6td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reddit-dark" /></template>

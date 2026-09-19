<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuxjtbc2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":439,"height":512};
const content = `<path class="yuxjtbc2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:prettier" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfwndcr0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":293,"height":512};
const content = `<path class="vfwndcr0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pure" /></template>

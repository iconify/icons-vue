<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-_hd-q4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":462,"height":512};
const content = `<path class="m-_hd-q4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:yasm" /></template>

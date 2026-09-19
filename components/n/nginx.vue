<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftuj4zbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ftuj4zbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nginx" /></template>

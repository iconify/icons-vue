<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngd4hgbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ngd4hgbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:webvtt" /></template>

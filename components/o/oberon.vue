<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y49me6bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y49me6bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:oberon" /></template>

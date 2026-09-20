<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c48_sfsxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c48_sfsxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pyshelf-dark" /></template>

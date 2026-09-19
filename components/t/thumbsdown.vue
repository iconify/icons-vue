<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og9akcckz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="og9akcckz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:thumbsdown" /></template>

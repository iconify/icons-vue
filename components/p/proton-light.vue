<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9fln6bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c9fln6bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-light" /></template>

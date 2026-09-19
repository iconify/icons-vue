<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ig1fb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7ig1fb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:pulse" /></template>

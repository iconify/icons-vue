<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x153h1baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x153h1baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pango" /></template>

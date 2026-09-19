<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhrruzb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rhrruzb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play-back-outline" /></template>

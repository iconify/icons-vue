<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyfq0hydv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyfq0hydv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radarr-light" /></template>

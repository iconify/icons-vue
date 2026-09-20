<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5v1u61ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w5v1u61ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:obs-bygg-light" /></template>

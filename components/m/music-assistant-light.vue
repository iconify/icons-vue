<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la_4ipbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="la_4ipbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:music-assistant-light" /></template>

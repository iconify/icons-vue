<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr9aj_vax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yr9aj_vax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paperclip-48" /></template>

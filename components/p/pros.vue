<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkf-omo-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wkf-omo-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pros" /></template>

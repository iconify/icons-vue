<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6l40enkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m6l40enkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zipcaptions-light" /></template>

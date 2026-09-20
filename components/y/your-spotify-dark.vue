<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trb9ibbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="trb9ibbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:your-spotify-dark" /></template>

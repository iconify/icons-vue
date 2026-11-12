<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi-7frb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fi-7frb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sonarr-light" /></template>

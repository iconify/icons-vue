<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sps-9q4ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sps-9q4ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radarr-anime-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i71qmgjcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i71qmgjcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:windows-retro-dark" /></template>

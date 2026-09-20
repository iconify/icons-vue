<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3vlycc2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3vlycc2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-tiles-dark" /></template>

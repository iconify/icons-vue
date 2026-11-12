<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfnk40wny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rfnk40wny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mediamtx-dark" /></template>

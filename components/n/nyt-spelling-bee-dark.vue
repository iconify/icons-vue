<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg9qh-kkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eg9qh-kkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-spelling-bee-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctf2s_bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ctf2s_bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:video-player" /></template>

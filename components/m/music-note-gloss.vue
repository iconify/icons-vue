<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sej40yb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sej40yb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:music-note-gloss" /></template>

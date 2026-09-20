<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by2a68kvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by2a68kvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:music-note-slash-expressive" /></template>

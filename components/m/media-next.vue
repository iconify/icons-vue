<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs-mlfnuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs-mlfnuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-next" /></template>

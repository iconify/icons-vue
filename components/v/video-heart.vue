<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fitd60bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fitd60bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:video-heart" /></template>

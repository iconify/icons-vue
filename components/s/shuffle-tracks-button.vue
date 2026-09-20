<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaepzkbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="gaepzkbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:shuffle-tracks-button" /></template>

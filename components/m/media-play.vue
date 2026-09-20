<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyr_hyy0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyr_hyy0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-play" /></template>

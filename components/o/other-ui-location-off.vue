<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwildgbog.css';
import '../../css/m/mfymmub6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bwildgbog"/><path class="mfymmub6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-location-off" /></template>

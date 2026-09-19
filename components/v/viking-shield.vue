<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyfl8jbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oyfl8jbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:viking-shield" /></template>

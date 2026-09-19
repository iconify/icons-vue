<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuzjs9mod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cuzjs9mod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:stereo-perspective" /></template>

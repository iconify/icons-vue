<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaaeg5bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="qaaeg5bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:menu-top-left" /></template>

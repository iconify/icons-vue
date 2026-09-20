<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhw2sablr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fhw2sablr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:slack-solid" /></template>

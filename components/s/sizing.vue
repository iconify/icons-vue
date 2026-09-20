<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si4f12egu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="si4f12egu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sizing" /></template>

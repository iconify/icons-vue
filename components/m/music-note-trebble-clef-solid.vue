<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl_8k3bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nl_8k3bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:music-note-trebble-clef-solid" /></template>

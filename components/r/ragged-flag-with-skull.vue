<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl0md4byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nl0md4byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ragged-flag-with-skull" /></template>

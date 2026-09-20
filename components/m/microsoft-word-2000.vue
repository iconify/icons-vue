<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5qmmgbfo.css';
import '../../css/p/p-r-fqbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i5qmmgbfo"/><path class="p-r-fqbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-word-2000" /></template>

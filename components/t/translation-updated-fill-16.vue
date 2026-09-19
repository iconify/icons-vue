<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srky2gbgm.css';
import '../../css/n/nkc71p2ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="srky2gbgm"/><path class="nkc71p2ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-updated-fill-16" /></template>

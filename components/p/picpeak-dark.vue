<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw55eobve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mw55eobve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:picpeak-dark" /></template>

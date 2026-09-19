<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dopxjy2hi.css';
import '../../css/r/rs80463iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dopxjy2hi"/><path class="rs80463iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:shuffle-outline" /></template>

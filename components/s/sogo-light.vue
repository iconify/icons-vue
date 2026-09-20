<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsni9xlze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jsni9xlze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sogo-light" /></template>

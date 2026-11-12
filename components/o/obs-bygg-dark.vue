<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhrhopb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dhrhopb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:obs-bygg-dark" /></template>

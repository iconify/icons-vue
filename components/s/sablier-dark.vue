<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htd18rb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="htd18rb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sablier-dark" /></template>

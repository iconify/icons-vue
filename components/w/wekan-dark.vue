<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw3mel2bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uw3mel2bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wekan-dark" /></template>

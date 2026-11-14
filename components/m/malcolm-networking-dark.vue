<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7yh9bb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w7yh9bb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:malcolm-networking-dark" /></template>

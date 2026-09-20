<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rexw2ywar.css';
import '../../css/s/sf5m5dbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rexw2ywar"/><path class="sf5m5dbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:verdaccio-dark" /></template>

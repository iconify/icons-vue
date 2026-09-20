<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c24on08cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c24on08cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:travstats-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kun_1n6hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kun_1n6hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plex-light" /></template>

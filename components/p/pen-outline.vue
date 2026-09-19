<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwuwdpb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rwuwdpb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pen-outline" /></template>

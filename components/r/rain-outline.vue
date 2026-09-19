<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn9in6okr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nn9in6okr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:rain-outline" /></template>

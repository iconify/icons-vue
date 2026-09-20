<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1_9nob6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="f1_9nob6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:whale-watching" /></template>

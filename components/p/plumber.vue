<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb9f9lq0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="lb9f9lq0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:plumber" /></template>

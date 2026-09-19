<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tetntvipe.css';
import '../../css/w/wczsurb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tetntvipe"/><path class="wczsurb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning-alt" /></template>

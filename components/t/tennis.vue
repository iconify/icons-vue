<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0x5bsqdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="f0x5bsqdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:tennis" /></template>

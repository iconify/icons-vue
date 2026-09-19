<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi2813bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mi2813bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:thumb-up-down" /></template>

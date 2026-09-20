<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi9jj-4wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="oi9jj-4wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:university" /></template>

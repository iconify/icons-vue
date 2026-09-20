<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wom0nulsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="wom0nulsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:sign-language" /></template>

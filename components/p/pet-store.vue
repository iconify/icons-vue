<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jem06bpnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="jem06bpnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:pet-store" /></template>

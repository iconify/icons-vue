<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu_j0cbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="vu_j0cbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:synagogue" /></template>

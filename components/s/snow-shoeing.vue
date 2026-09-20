<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hetltv1hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="hetltv1hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:snow-shoeing" /></template>

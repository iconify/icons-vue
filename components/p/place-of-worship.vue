<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogg4ex6bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ogg4ex6bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:place-of-worship" /></template>

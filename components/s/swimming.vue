<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvkc8whus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="pvkc8whus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:swimming" /></template>

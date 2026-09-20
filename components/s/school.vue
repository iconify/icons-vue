<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqrahty2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="jqrahty2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:school" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdpoi43ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdpoi43ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:motorcycle" /></template>

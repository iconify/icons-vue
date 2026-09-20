<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjoe9x-2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="jjoe9x-2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:post-office" /></template>

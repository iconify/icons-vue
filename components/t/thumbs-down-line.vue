<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5ye4n3wv.css';
import '../../css/f/fr_geojnw.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 p5ye4n3wv"/><path class="clr-i-outline clr-i-outline-path-2 fr_geojnw"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:thumbs-down-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zte0-4eja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zte0-4eja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:world-map-alt" /></template>

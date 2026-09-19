<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoaouj8_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="eoaouj8_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:wfs-t" /></template>

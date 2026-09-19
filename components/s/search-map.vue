<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih1ndobif.css';
import '../../css/c/cy7ufpbyc.css';
import '../../css/h/hymfp_bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ih1ndobif"/><path class="cy7ufpbyc"/><path class="hymfp_bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:search-map" /></template>

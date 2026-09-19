<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kep1zf04e.css';
import '../../css/n/na94o3ufs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="kep1zf04e"/><path class="na94o3ufs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-user" /></template>

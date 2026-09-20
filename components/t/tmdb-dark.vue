<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgw5xlb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qgw5xlb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tmdb-dark" /></template>

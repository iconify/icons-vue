<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5twlibpq.css';
import '../../css/d/dkab58b3o.css';
import '../../css/z/zn725acau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5twlibpq"/><path class="dkab58b3o"/><path class="zn725acau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tidyquest" /></template>

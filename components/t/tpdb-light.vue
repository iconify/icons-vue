<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moj3q8fhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="moj3q8fhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tpdb-light" /></template>

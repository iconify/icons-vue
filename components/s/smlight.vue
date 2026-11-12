<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1cxj__-m.css';
import '../../css/a/a5t35j_6j.css';
import '../../css/w/w3mbvw3se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="y1cxj__-m"/><circle class="a5t35j_6j"/><circle class="w3mbvw3se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smlight" /></template>

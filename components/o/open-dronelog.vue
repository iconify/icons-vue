<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcnly3b_c.css';
import '../../css/g/gtz84wbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pcnly3b_c"/><path class="gtz84wbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:open-dronelog" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orvizdb2o.css';
import '../../css/h/hluiizbfv.css';
import '../../css/b/b0n25wb5s.css';
import '../../css/i/i1sd5pehr.css';
import '../../css/v/v0ka02b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="orvizdb2o"/><path class="hluiizbfv"/><path class="b0n25wb5s"/><path class="i1sd5pehr"/><path class="v0ka02b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:statcom-48-bold" /></template>

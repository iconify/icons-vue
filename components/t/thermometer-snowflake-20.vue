<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6zve7bwi.css';
import '../../css/p/ppk8d-n1m.css';
import '../../css/d/dyrpvlfpb.css';
import '../../css/p/px1s3hbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x6zve7bwi"/><path class="ppk8d-n1m"/><path class="dyrpvlfpb"/><path class="px1s3hbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-snowflake-20" /></template>

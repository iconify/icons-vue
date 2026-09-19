<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7rnddcql.css';
import '../../css/h/hfbu_gb2s.css';
import '../../css/d/dk5j2el3g.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 w7rnddcql"/><path class="clr-i-outline clr-i-outline-path-2 hfbu_gb2s"/><path class="clr-i-outline clr-i-outline-path-3 dk5j2el3g"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:node-group-line" /></template>

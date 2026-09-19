<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmg2hgb8g.css';
import '../../css/d/dcxprjszn.css';
import '../../css/s/sjrvryb6o.css';
import '../../css/h/hgv60rb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="pmg2hgb8g"/><circle class="dcxprjszn"/><circle class="sjrvryb6o"/><path class="hgv60rb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:share-social-outline" /></template>

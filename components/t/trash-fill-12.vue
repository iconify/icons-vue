<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srz00hnfq.css';
import '../../css/d/dl1wr10wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="srz00hnfq"/><path class="dl1wr10wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:trash-fill-12" /></template>

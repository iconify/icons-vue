<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5is1to6c.css';
import '../../css/u/ud1-bgmma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r5is1to6c"/><path class="ud1-bgmma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opentelemetry" /></template>

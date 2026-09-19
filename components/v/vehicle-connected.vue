<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb4s33bah.css';
import '../../css/r/rtki51b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kb4s33bah"/><path class="rtki51b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:vehicle-connected" /></template>

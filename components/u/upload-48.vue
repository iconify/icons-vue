<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upy-ybcph.css';
import '../../css/i/iw2o35bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="upy-ybcph"/><path class="iw2o35bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:upload-48" /></template>

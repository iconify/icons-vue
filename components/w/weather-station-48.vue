<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffgo8jbww.css';
import '../../css/y/yzrxcvbma.css';
import '../../css/o/o-o8tgb3f.css';
import '../../css/i/i-i_4rewx.css';
import '../../css/a/azjk1obih.css';
import '../../css/n/nh3pp-bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ffgo8jbww"/><path class="yzrxcvbma"/><path class="o-o8tgb3f"/><path class="i-i_4rewx"/><path class="azjk1obih"/><path class="nh3pp-bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:weather-station-48" /></template>

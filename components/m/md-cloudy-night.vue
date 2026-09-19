<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4xyx_bsy.css';
import '../../css/o/o-00tsbmu.css';
import '../../css/k/kr677l0as.css';
import '../../css/a/arqavzbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p4xyx_bsy"/><path class="o-00tsbmu"/><path class="kr677l0as"/><path class="arqavzbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-cloudy-night" /></template>

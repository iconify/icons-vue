<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl5zwabiv.css';
import '../../css/q/qm-avg1-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yl5zwabiv"/><path class="qm-avg1-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nomad-wordmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze2v6yb1y.css';
import '../../css/s/sh_nibbxh.css';
import '../../css/t/tznu3_bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ze2v6yb1y"/><circle class="sh_nibbxh"/><path class="tznu3_bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:recording-outline" /></template>

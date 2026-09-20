<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-4_v9njk.css';
import '../../css/d/dw2j3ebeq.css';
import '../../css/s/st1ujobif.css';
import '../../css/r/r25huvknw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m-4_v9njk"/><path class="dw2j3ebeq"/><path class="st1ujobif"/><path class="r25huvknw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openshift" /></template>

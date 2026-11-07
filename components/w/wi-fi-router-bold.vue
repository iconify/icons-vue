<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ullszbbqu.css';
import '../../css/d/dy4_z9gcp.css';
import '../../css/y/yfs8wlcdx.css';
import '../../css/l/lf_p4sb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ullszbbqu"/><path class="dy4_z9gcp"/><path class="yfs8wlcdx"/><path clip-rule="evenodd" class="lf_p4sb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-router-bold" /></template>

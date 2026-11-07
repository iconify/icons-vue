<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhbb46vhn.css';
import '../../css/m/m_kry2xln.css';
import '../../css/m/m41j1im6l.css';
import '../../css/v/vh0iqwbmx.css';
import '../../css/h/hcbdb2o-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhbb46vhn"/><path class="m_kry2xln"/><path class="m41j1im6l"/><path class="vh0iqwbmx"/><path class="hcbdb2o-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:thermometer-bold-duotone" /></template>

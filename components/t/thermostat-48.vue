<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hac57wbhi.css';
import '../../css/t/trvs23rbx.css';
import '../../css/s/svhavybtd.css';
import '../../css/p/pb6h54xlu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hac57wbhi"/><path class="trvs23rbx"/><path class="svhavybtd"/><path class="pb6h54xlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermostat-48" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8ovs__gx.css';
import '../../css/b/bhg_0dbbc.css';
import '../../css/y/yhupigbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y8ovs__gx"/><path class="bhg_0dbbc"/><path class="yhupigbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:medal-48" /></template>

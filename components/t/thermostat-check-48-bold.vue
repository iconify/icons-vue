<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmynvjkbh.css';
import '../../css/f/fdug528jx.css';
import '../../css/p/piqbfhj8g.css';
import '../../css/q/qnjenrxnq.css';
import '../../css/o/ovk2mbcep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qmynvjkbh"/><path class="fdug528jx"/><path class="piqbfhj8g"/><path class="qnjenrxnq"/><path class="ovk2mbcep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermostat-check-48-bold" /></template>

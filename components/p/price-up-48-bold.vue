<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcp6u-oop.css';
import '../../css/x/xgx2z7ryy.css';
import '../../css/o/o4v1t0brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qcp6u-oop"/><path class="xgx2z7ryy"/><path class="o4v1t0brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:price-up-48-bold" /></template>

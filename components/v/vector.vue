<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt6er0bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xt6er0bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:vector" /></template>

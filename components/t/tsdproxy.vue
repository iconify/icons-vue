<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl35fttde.css';
import '../../css/v/vv1q87bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="yl35fttde"/><path class="vv1q87bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tsdproxy" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jedolt31x.css';
import '../../css/w/wdqxtccbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jedolt31x"/><path class="wdqxtccbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:remoteterm" /></template>

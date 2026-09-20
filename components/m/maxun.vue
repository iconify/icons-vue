<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx0rambyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mx0rambyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:maxun" /></template>

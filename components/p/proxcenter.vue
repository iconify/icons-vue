<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs16rbccl.css';
import '../../css/t/t9suffddk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vs16rbccl"/><path class="t9suffddk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proxcenter" /></template>

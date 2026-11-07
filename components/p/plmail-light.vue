<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2n33z6pt.css';
import '../../css/d/dr_uzfb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f2n33z6pt"/><path class="dr_uzfb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plmail-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9irpyjfv.css';
import '../../css/o/opkm_bb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a9irpyjfv"/><path class="opkm_bb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:mic-outline" /></template>

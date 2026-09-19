<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srsb_8zfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="srsb_8zfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:network" /></template>

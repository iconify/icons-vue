<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbqepq-ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hbqepq-ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:screenlite-light" /></template>

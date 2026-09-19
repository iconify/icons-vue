<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8pcxmt_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":392,"height":480};
const content = `<path class="x8pcxmt_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-setup" /></template>

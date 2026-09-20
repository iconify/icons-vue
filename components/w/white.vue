<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg24lgbwn.css';
import '../../css/u/ut59o-b4c.css';
import '../../css/a/acq_ddcuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg24lgbwn"/><path class="ut59o-b4c"/><path class="acq_ddcuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:white" /></template>

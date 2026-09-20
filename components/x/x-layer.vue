<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuma_8b1z.css';
import '../../css/m/m0f02wb3t.css';
import '../../css/x/xq54x2m2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuma_8b1z"/><path class="m0f02wb3t"/><path class="xq54x2m2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:x-layer" /></template>

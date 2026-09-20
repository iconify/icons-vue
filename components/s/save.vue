<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz542cbqq.css';
import '../../css/r/rv4rin_vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz542cbqq"/><path class="rv4rin_vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:save" /></template>

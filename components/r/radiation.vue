<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqchobbzt.css';
import '../../css/v/v4i2ew1ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqchobbzt"/><circle class="v4i2ew1ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:radiation" /></template>

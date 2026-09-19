<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4i2ew1ke.css';
import '../../css/d/dlc29abjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="v4i2ew1ke"/><path class="dlc29abjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:target-lock" /></template>

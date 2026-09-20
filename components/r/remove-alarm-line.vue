<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvsekgbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvsekgbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:remove-alarm-line" /></template>

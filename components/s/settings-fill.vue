<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6wz8cb3t.css';
import '../../css/w/wghzjz1_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="t6wz8cb3t"/><path class="wghzjz1_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:settings-fill" /></template>

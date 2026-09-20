<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueu-zdbxw.css';
import '../../css/m/m_hk1_b6x.css';
import '../../css/g/g4uvfabpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueu-zdbxw"/><path class="m_hk1_b6x"/><path class="g4uvfabpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:zen" /></template>

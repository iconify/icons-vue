<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub35knbuk.css';
import '../../css/d/d_qmu7ifq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub35knbuk"/><path class="d_qmu7ifq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:teer" /></template>

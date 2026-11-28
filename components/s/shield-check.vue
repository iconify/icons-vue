<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofg_qd6-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofg_qd6-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:shield-check" /></template>

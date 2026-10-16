<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbl98olvj.css';
import '../../css/d/drqiwqb8a.css';
import '../../css/o/o22z116ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nbl98olvj"/><path class="drqiwqb8a"/><path class="o22z116ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pelton-wheel-48" /></template>

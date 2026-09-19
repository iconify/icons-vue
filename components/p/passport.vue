<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf-zqubsq.css';
import '../../css/k/kb9hd4ajm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="cf-zqubsq"/><path class="kb9hd4ajm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:passport" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9fdhsw1j.css';
import '../../css/q/qjpjf_bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m9fdhsw1j"/><path class="qjpjf_bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monopile-20" /></template>

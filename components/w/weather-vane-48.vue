<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hot0jtf_c.css';
import '../../css/p/p8swzyblw.css';
import '../../css/i/izs6c-bvl.css';
import '../../css/t/tqe-v7b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hot0jtf_c"/><path class="p8swzyblw"/><path class="izs6c-bvl"/><path class="tqe-v7b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:weather-vane-48" /></template>

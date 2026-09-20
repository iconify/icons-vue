<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdo88m09q.css';
import '../../css/k/k3v_cudyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tdo88m09q"/><path class="k3v_cudyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:stats-up" /></template>

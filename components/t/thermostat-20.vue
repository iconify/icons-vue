<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw3xaacjo.css';
import '../../css/q/q-d9kh0tc.css';
import '../../css/m/m0qa3fayh.css';
import '../../css/k/kiknbdcxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="q-d9kh0tc"/><path class="m0qa3fayh"/><path class="kiknbdcxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermostat-20" /></template>

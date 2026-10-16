<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zerildbqi.css';
import '../../css/k/kziqmybgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zerildbqi"/><path class="kziqmybgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-inverter-off-48" /></template>

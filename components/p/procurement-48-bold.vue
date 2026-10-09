<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugy_83khr.css';
import '../../css/t/trs0klbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ugy_83khr"/><path class="trs0klbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:procurement-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjz_t6bds.css';
import '../../css/q/q4r8_6iob.css';
import '../../css/t/t100656sa.css';
import '../../css/v/vfuw7m6dq.css';
import '../../css/b/bdof1db3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gjz_t6bds"/><path class="q4r8_6iob"/><path class="t100656sa"/><path class="vfuw7m6dq"/><path class="bdof1db3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:turbine-icing-48" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5rak2bbx.css';
import '../../css/i/iyuvrebaw.css';
import '../../css/c/cnvsi8cop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m5rak2bbx"/><path class="iyuvrebaw"/><path class="cnvsi8cop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plumb-bob-48-bold" /></template>

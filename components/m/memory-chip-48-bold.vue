<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cibn_julo.css';
import '../../css/e/epdoheazy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cibn_julo"/><path class="epdoheazy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:memory-chip-48-bold" /></template>

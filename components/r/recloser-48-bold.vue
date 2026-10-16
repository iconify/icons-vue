<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c876zybxx.css';
import '../../css/t/tp2ceobty.css';
import '../../css/h/h3cp2fcos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c876zybxx"/><path class="tp2ceobty"/><path class="h3cp2fcos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:recloser-48-bold" /></template>

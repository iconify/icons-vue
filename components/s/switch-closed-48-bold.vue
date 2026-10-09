<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkwabjk_z.css';
import '../../css/e/e268v4bmv.css';
import '../../css/p/py6masfhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kkwabjk_z"/><path class="e268v4bmv"/><path class="py6masfhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:switch-closed-48-bold" /></template>

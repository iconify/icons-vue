<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t55dglbwd.css';
import '../../css/i/i2dsa1fpp.css';
import '../../css/m/mpef91b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t55dglbwd"/><path class="i2dsa1fpp"/><path class="mpef91b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:passkey-48-bold" /></template>

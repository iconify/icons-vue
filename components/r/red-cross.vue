<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/h/hrq90hfel.css';
import '../../css/h/hbze5o9pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><circle class="hrq90hfel"/><path class="hbze5o9pm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:red-cross" /></template>

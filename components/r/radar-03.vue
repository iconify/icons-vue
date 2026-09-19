<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/mm4eu-bgy.css';
import '../../css/a/akzoi-bci.css';
import '../../css/e/eoh8kjxii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mm4eu-bgy"/><path class="akzoi-bci"/><path class="eoh8kjxii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:radar-03" /></template>

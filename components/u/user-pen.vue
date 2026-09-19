<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/o50j3bb0t.css';
import '../../css/e/ei7gp9r8j.css';
import '../../css/h/hrld5ibxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o50j3bb0t"/><circle class="ei7gp9r8j"/><path class="hrld5ibxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-pen" /></template>

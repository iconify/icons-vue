<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv_hji6de.css';
import '../../css/h/hyq0q9b8g.css';
import '../../css/q/qjp63yb9e.css';
import '../../css/x/xs03_8unf.css';
import '../../css/k/kqg7wdbzl.css';
import '../../css/x/xlara-bno.css';
import '../../css/c/culfoohto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="hyq0q9b8g"/><path class="qjp63yb9e"/><path class="xs03_8unf"/><path class="kqg7wdbzl"/><path clip-rule="evenodd" class="xlara-bno"/><path clip-rule="evenodd" class="culfoohto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-square-bold-duotone" /></template>

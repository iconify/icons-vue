<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mopdhnbdd.css';
import '../../css/m/ml6irbcyc.css';
import '../../css/j/j2yb1ab3d.css';
import '../../css/k/kyo440vyg.css';
import '../../css/c/cf1mp-bbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="mopdhnbdd"/><path class="ml6irbcyc"/><path class="j2yb1ab3d"/><path class="kyo440vyg"/><circle class="cf1mp-bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:sandbox-outlined" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghgg4x8rk.css';
import '../../css/y/ymi4owbyw.css';
import '../../css/t/tkcwycyff.css';
import '../../css/q/qygy3o62o.css';
import '../../css/b/bdkl8-dne.css';
import '../../css/j/j3cy-fbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ghgg4x8rk"/><path class="ymi4owbyw"/><path class="tkcwycyff"/><path class="qygy3o62o"/><path class="bdkl8-dne"/><path class="j3cy-fbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-meter-x-48" /></template>

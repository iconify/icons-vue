<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghgg4x8rk.css';
import '../../css/y/ymi4owbyw.css';
import '../../css/t/tkcwycyff.css';
import '../../css/q/qygy3o62o.css';
import '../../css/z/z4sj3ixdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ghgg4x8rk"/><path class="ymi4owbyw"/><path class="tkcwycyff"/><path class="qygy3o62o"/><path class="z4sj3ixdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-meter-check-48" /></template>

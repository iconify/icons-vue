<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcwfyf16x.css';
import '../../css/l/lfgx0yqjl.css';
import '../../css/g/gvtf67ctb.css';
import '../../css/u/ucn402gew.css';
import '../../css/k/kuaiedclu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pcwfyf16x"/><path class="lfgx0yqjl"/><path class="gvtf67ctb"/><path class="ucn402gew"/><path class="kuaiedclu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trash-restore-48-bold" /></template>

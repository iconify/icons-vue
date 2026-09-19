<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5vc2lbnc.css';
import '../../css/o/o70nwy-rj.css';
import '../../css/h/hr1b_yvco.css';
import '../../css/i/its46bcpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l5vc2lbnc"/><circle class="o70nwy-rj"/><circle class="hr1b_yvco"/><circle class="its46bcpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:options-outline" /></template>

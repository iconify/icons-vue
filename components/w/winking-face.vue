<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az7hstbmu.css';
import '../../css/o/o493bgqoz.css';
import '../../css/y/yibo3vftr.css';
import '../../css/v/v7et8abwg.css';
import '../../css/a/azcwg7e-d.css';
import '../../css/o/otit0l4ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><path class="o493bgqoz"/><path class="yibo3vftr"/><path class="v7et8abwg"/><circle class="azcwg7e-d"/><circle class="otit0l4ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:winking-face" /></template>

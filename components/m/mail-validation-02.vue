<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gngy5vaph.css';
import '../../css/q/qsez0nite.css';
import '../../css/e/e5jfj3b2v.css';
import '../../css/m/mfg1gacjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gngy5vaph"/><path class="qsez0nite"/><path class="e5jfj3b2v"/><path class="mfg1gacjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-validation-02" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bqxzm4b2o.css';
import '../../css/k/kj2l08bic.css';
import '../../css/t/t4b00jbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="bqxzm4b2o"/><path class="kj2l08bic"/><path class="t4b00jbkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:pen" /></template>

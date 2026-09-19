<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhpmsjbax.css';
import '../../css/t/t-jbtsufb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="qhpmsjbax"/><path class="t-jbtsufb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:question-mark-stroke-16" /></template>

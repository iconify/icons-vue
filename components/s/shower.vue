<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_shbeese.css';
import '../../css/y/yn8tzubog.css';
import '../../css/g/g7i4sdbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q_shbeese"/><path class="yn8tzubog"/><path class="g7i4sdbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:shower" /></template>

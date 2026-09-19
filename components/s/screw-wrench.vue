<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtfewx74d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="xtfewx74d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:screw-wrench" /></template>

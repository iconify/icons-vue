<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx7mr1bdl.css';
import '../../css/z/zp52ksh9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="wx7mr1bdl"/><path class="zp52ksh9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:retroassembly" /></template>

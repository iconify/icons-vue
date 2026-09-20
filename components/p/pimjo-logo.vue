<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvolx0pqg.css';
import '../../css/e/ex_99rxvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvolx0pqg"/><path class="ex_99rxvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pimjo-logo" /></template>

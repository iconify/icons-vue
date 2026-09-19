<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovsyq3krw.css';
import '../../css/r/r4-qnybet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ovsyq3krw"/><circle class="r4-qnybet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:question-mark-stroke-12" /></template>

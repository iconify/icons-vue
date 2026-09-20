<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt54wcczy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tt54wcczy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:payment-cash-out-3-remix" /></template>

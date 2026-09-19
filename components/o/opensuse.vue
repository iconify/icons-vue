<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0n8thbpp.css';
import '../../css/a/azwi-ublj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q0n8thbpp"/><path class="azwi-ublj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:opensuse" /></template>

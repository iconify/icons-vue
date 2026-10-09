<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0ao8hbvl.css';
import '../../css/s/ssm6s4b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q0ao8hbvl"/><path class="ssm6s4b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:subsea-cable-48-bold" /></template>

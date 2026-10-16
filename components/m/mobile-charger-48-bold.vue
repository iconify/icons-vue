<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcjo-6bpf.css';
import '../../css/g/gjx6_nbye.css';
import '../../css/f/f9s4ogcoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gcjo-6bpf"/><path class="gjx6_nbye"/><path class="f9s4ogcoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mobile-charger-48-bold" /></template>

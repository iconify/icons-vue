<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfzdd5bmi.css';
import '../../css/b/bbxn-dufo.css';
import '../../css/k/kem81wb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gfzdd5bmi"/><path class="bbxn-dufo"/><path class="kem81wb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:users-plus-48" /></template>

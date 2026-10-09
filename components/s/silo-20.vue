<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik-dwhbem.css';
import '../../css/b/bp5qez_qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ik-dwhbem"/><path class="bp5qez_qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:silo-20" /></template>

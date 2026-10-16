<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-e81vb3y.css';
import '../../css/n/nlgovibwp.css';
import '../../css/e/ek-1xpvww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i-e81vb3y"/><path class="nlgovibwp"/><path class="ek-1xpvww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pcb-20" /></template>

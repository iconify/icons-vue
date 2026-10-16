<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa3cy-byb.css';
import '../../css/e/e2lawp-2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xa3cy-byb"/><path class="e2lawp-2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:or-gate-20-bold" /></template>

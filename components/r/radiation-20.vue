<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2-3n8bey.css';
import '../../css/q/q7a8l0b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a2-3n8bey"/><path class="q7a8l0b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:radiation-20" /></template>

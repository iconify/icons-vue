<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcso7vx-z.css';
import '../../css/f/f6wni1b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="gcso7vx-z"/><path class="f6wni1b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:pytorch" /></template>

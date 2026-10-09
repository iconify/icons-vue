<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjut8esur.css';
import '../../css/u/ujxou552b.css';
import '../../css/h/h02k7abwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tjut8esur"/><path class="ujxou552b"/><path class="h02k7abwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:megaphone-48-bold" /></template>

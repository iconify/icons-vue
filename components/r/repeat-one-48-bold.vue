<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc4ommb6u.css';
import '../../css/i/it-ce4kqj.css';
import '../../css/r/rawgbsbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oc4ommb6u"/><path class="it-ce4kqj"/><path class="rawgbsbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:repeat-one-48-bold" /></template>

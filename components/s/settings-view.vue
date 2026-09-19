<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiv92mbuz.css';
import '../../css/u/ufl34_bei.css';
import '../../css/l/lcu33ccze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="tiv92mbuz"/><path class="ufl34_bei"/><path class="lcu33ccze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:settings-view" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cya1rgi2m.css';
import '../../css/p/pzrl0qlzj.css';
import '../../css/m/mia-jjxeq.css';
import '../../css/f/fw7pardmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="cya1rgi2m"/><path class="pzrl0qlzj"/><path class="mia-jjxeq"/><path class="fw7pardmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wifi" /></template>

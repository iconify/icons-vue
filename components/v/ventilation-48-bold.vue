<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfpjugbvy.css';
import '../../css/i/ie8kakb8r.css';
import '../../css/o/oer3qjgyj.css';
import '../../css/t/t84yf1bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfpjugbvy"/><path class="ie8kakb8r"/><path class="oer3qjgyj"/><path class="t84yf1bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ventilation-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6pg-hzok.css';
import '../../css/i/i8cbj5bwx.css';
import '../../css/o/o-urmp0yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r6pg-hzok"/><path class="i8cbj5bwx"/><path class="o-urmp0yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:reply-all-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv51c3bzy.css';
import '../../css/h/h09j6xbhq.css';
import '../../css/p/p1u31l47s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nv51c3bzy"/><path class="h09j6xbhq"/><path class="p1u31l47s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermocouple-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1iv3qhdn.css';
import '../../css/d/de1hnzbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d1iv3qhdn"/><path class="de1hnzbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:microgrid-48" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrpvxrlxf.css';
import '../../css/b/bxzxb8v8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vrpvxrlxf"/><path class="bxzxb8v8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-alert-48" /></template>

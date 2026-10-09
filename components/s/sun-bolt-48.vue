<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f70j8yk4i.css';
import '../../css/m/mytw5ubob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f70j8yk4i"/><path class="mytw5ubob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-bolt-48" /></template>

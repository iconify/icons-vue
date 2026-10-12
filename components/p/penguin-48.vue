<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wibsj_byf.css';
import '../../css/w/w303u3a6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wibsj_byf"/><path class="w303u3a6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:penguin-48" /></template>

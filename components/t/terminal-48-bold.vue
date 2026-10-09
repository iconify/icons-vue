<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woaiz3jcj.css';
import '../../css/t/t2uupdbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="woaiz3jcj"/><path class="t2uupdbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:terminal-48-bold" /></template>

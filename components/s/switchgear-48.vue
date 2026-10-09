<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9jb7kaqf.css';
import '../../css/j/jimnbhblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m9jb7kaqf"/><path class="jimnbhblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:switchgear-48" /></template>

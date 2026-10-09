<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twx0_4--t.css';
import '../../css/s/s9uy0jb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="twx0_4--t"/><path class="s9uy0jb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:silo-48" /></template>

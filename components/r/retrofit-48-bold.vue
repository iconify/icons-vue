<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxvnz_b5x.css';
import '../../css/x/x1l7c_xru.css';
import '../../css/m/m9o881-gj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uxvnz_b5x"/><path class="x1l7c_xru"/><path class="m9o881-gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:retrofit-48-bold" /></template>

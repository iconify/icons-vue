<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h29-mkxmi.css';
import '../../css/d/d4ur63wtm.css';
import '../../css/i/ih216efdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h29-mkxmi"/><path clip-rule="evenodd" class="d4ur63wtm"/><path class="ih216efdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:swiss-knife-16" /></template>

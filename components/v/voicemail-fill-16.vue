<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/v/vi1e7rb5q.css';
import '../../css/l/lncnfvbwz.css';
import '../../css/g/glfhpzbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="flen3tbdj"><circle class="vi1e7rb5q"/><circle class="lncnfvbwz"/><path class="glfhpzbry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:voicemail-fill-16" /></template>

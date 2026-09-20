<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4kqh8bxz.css';
import '../../css/e/ep6tlrbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p4kqh8bxz"/><path class="ep6tlrbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:surveyjs" /></template>

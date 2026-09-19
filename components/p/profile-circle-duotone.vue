<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/ht8aw2boj.css';
import '../../css/t/t4me6eb9h.css';
import '../../css/y/y_9la8ijd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ht8aw2boj"/><path class="t4me6eb9h"/><path class="y_9la8ijd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:profile-circle-duotone" /></template>

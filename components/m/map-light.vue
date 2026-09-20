<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t98jbcwdn.css';
import '../../css/m/msqpicc3e.css';
import '../../css/b/bkyqy-baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t98jbcwdn"/><path class="msqpicc3e"/><circle class="bkyqy-baq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:map-light" /></template>

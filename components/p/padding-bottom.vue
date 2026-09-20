<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8k9kjbqe.css';
import '../../css/u/u_90zur1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t8k9kjbqe"/><path class="u_90zur1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:padding-bottom" /></template>

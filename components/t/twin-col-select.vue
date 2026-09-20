<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqx-vr3bx.css';
import '../../css/m/mj3ha3b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kqx-vr3bx"/><path class="mj3ha3b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:twin-col-select" /></template>

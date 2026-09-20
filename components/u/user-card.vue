<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqe-vxb7s.css';
import '../../css/c/c_hslm9lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cqe-vxb7s"/><path class="c_hslm9lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:user-card" /></template>

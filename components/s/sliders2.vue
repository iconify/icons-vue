<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws0_qmb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ws0_qmb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sliders2" /></template>

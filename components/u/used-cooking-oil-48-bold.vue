<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyo9awbxy.css';
import '../../css/i/iip25ub1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fyo9awbxy"/><path class="iip25ub1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:used-cooking-oil-48-bold" /></template>

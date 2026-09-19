<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irskxtb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="irskxtb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:metro" /></template>

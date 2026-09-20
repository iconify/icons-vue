<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8-frc3ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t8-frc3ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:swap-left" /></template>

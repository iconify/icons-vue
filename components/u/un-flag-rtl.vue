<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hybtnqbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hybtnqbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:un-flag-rtl" /></template>

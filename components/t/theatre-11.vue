<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_luvib9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="t_luvib9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:theatre-11" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo9_91b2k.css';
import '../../css/a/a79tt-b_j.css';
import '../../css/q/q2lkf7xso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uo9_91b2k"/><path class="a79tt-b_j"/><path class="q2lkf7xso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stargazing-20-bold" /></template>

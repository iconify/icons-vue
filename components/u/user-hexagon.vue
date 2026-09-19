<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-kwgp5vg.css';
import '../../css/u/ujjz19bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-kwgp5vg"/><path class="ujjz19bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-hexagon" /></template>

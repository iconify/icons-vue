<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw6k_dayf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":628,"height":694};
const content = `<path class="fw6k_dayf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:umbrella" /></template>

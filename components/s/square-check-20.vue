<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c961mpvnt.css';
import '../../css/f/f_m6gmbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c961mpvnt"/><path class="f_m6gmbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-check-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo8-8l0ji.css';
import '../../css/n/nd0nkt-ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lo8-8l0ji"/><path class="nd0nkt-ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:set-square-20-bold" /></template>

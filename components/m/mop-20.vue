<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecjx1yg4j.css';
import '../../css/l/l6k0rd2qb.css';
import '../../css/g/gzcgyebif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ecjx1yg4j"/><path class="l6k0rd2qb"/><path class="gzcgyebif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mop-20" /></template>

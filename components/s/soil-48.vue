<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzh-h4k4i.css';
import '../../css/l/lvvelyb5g.css';
import '../../css/r/r9j5p4bxh.css';
import '../../css/u/ux587345u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jzh-h4k4i"/><path class="lvvelyb5g"/><path class="r9j5p4bxh"/><path class="ux587345u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:soil-48" /></template>

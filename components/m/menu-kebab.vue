<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/igc2mbcca.css';
import '../../css/l/l5goj9tdn.css';
import '../../css/a/abpbqzb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="igc2mbcca"/><circle class="l5goj9tdn"/><circle class="abpbqzb9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:menu-kebab" /></template>

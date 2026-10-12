<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy1qryb3w.css';
import '../../css/f/fd6b2rb5y.css';
import '../../css/p/pk3rcgb0u.css';
import '../../css/u/uxaxeqbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uy1qryb3w"/><path class="fd6b2rb5y"/><path class="pk3rcgb0u"/><path class="uxaxeqbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:taxi-20-bold" /></template>

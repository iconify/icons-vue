<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzou1z3xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pzou1z3xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:mask" /></template>

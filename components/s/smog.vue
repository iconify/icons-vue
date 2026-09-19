<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo3gpe9bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="zo3gpe9bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:smog" /></template>

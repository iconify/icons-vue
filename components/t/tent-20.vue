<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct17tacjl.css';
import '../../css/l/l9yqfvb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ct17tacjl"/><path class="l9yqfvb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tent-20" /></template>

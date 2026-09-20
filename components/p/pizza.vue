<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk5nofhuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rk5nofhuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pizza" /></template>

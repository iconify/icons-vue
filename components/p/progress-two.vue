<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el0eubbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="el0eubbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:progress-two" /></template>

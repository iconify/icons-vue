<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-5ur4b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p-5ur4b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:unlocked" /></template>

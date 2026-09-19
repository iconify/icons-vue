<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn3a8pm_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mn3a8pm_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:soundcloud" /></template>

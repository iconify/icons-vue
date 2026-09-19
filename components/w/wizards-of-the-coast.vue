<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtt81nbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="jtt81nbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:wizards-of-the-coast" /></template>

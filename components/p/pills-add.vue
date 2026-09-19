<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maueyoblv.css';
import '../../css/y/ymcl-hbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="maueyoblv"/><path class="ymcl-hbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pills-add" /></template>

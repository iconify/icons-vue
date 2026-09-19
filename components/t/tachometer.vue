<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t02myt54b.css';
import '../../css/n/nco21hbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t02myt54b"/><path class="nco21hbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:tachometer" /></template>

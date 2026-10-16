<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgljnwlus.css';
import '../../css/s/stlc3bbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192.46,"height":222.23};
const content = `<path class="jgljnwlus"/><path class="stlc3bbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tikv" /></template>

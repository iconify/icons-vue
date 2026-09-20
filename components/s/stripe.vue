<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znzk-c_8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":214};
const content = `<path class="znzk-c_8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:stripe" /></template>

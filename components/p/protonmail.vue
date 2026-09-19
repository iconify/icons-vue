<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ococizr3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ococizr3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:protonmail" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd-arsb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vd-arsb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:tools" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajr6vqxuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ajr6vqxuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mars-double" /></template>

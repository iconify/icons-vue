<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2hq8bblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="g2hq8bblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:theater-masks" /></template>

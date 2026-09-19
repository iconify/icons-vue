<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_31y-bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="l_31y-bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-drowning" /></template>

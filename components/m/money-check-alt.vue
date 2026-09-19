<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2gkt-kwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="v2gkt-kwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:money-check-alt" /></template>

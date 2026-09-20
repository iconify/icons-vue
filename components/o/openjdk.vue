<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unxzl60gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unxzl60gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openjdk" /></template>

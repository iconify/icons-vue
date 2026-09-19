<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f33f75blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":851,"height":1000};
const content = `<path class="f33f75blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:opera" /></template>

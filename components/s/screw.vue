<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp8ccub7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gp8ccub7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:screw" /></template>

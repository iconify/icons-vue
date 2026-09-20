<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7xnroufn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7xnroufn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pantheon" /></template>

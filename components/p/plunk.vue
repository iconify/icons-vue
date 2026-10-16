<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6mpagzxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1080,"height":1080};
const content = `<path class="k6mpagzxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:plunk" /></template>

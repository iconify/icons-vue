<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1m1ux7to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x1m1ux7to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:nebl" /></template>

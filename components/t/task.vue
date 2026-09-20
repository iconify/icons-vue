<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erq7k8buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erq7k8buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:task" /></template>

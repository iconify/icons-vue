<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-vmj1b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q-vmj1b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangle-left" /></template>

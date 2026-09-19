<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4u5kll7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4u5kll7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:remove-empty" /></template>

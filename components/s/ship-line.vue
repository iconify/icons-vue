<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k59qkab7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k59qkab7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ship-line" /></template>

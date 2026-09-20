<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pofwkcbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pofwkcbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:skull-above-crossed-cutlasses" /></template>

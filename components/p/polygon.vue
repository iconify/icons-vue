<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2jwcgbdq.css';
import '../../css/c/cu9d7nszf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f2jwcgbdq"/><path class="cu9d7nszf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:polygon" /></template>

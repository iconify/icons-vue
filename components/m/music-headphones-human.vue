<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1ygzubzy.css';
import '../../css/p/pjqpfrbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o1ygzubzy"/><path class="pjqpfrbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:music-headphones-human" /></template>

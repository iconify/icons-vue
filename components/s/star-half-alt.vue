<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlj2t5bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jlj2t5bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:star-half-alt" /></template>

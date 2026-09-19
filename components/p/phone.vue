<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl84s6vhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1408};
const content = `<path class="jl84s6vhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:phone" /></template>

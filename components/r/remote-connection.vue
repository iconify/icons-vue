<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_tkdut0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u_tkdut0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:remote-connection" /></template>

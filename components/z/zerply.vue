<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juqe5accg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="juqe5accg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:zerply" /></template>

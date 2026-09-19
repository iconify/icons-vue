<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvlvc6h1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pvlvc6h1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:people-carry-box" /></template>

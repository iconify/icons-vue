<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4m6t8bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="k4m6t8bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:meteorite" /></template>

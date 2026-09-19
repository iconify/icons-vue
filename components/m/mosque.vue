<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs9zi91gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="cs9zi91gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:mosque" /></template>

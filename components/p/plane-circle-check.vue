<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw8dj8x0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="aw8dj8x0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:plane-circle-check" /></template>

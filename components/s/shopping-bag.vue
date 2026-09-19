<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flm6eybvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="flm6eybvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:shopping-bag" /></template>

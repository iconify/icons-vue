<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7jzn3aob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r7jzn3aob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:slash" /></template>

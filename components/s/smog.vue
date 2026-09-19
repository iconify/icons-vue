<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1xy50bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="g1xy50bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:smog" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3w-4db8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z3w-4db8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:slashdot" /></template>

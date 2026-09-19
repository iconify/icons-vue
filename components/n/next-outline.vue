<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnobr9b0y.css';
import '../../css/s/svdy80z7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jnobr9b0y"/><path class="svdy80z7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:next-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpze4wb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="fpze4wb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:torah" /></template>

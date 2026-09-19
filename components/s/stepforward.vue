<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpb6u2b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":16};
const content = `<path class="dpb6u2b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:stepforward" /></template>

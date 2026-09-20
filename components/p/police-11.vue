<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch76cibil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ch76cibil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:police-11" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uky8qyb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="uky8qyb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:router" /></template>

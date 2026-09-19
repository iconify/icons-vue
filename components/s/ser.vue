<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpj3fdb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gpj3fdb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ser" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs09_bb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gs09_bb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:rugby" /></template>

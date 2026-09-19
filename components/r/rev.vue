<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db9rc0bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="db9rc0bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:rev" /></template>

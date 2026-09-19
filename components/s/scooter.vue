<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfl-uc04m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lfl-uc04m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:scooter" /></template>

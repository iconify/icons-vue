<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7tbn3bau.css';
import '../../css/u/uc95oo_ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g7tbn3bau"/><path class="uc95oo_ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:table-tennis-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdfbt41fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdfbt41fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sort-asc-24" /></template>

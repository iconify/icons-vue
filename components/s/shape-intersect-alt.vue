<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugeibnndd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugeibnndd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-intersect-alt" /></template>

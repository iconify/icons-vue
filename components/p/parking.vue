<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otzh3hbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otzh3hbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:parking" /></template>

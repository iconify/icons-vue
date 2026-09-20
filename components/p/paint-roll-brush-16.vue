<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at62glbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="at62glbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:paint-roll-brush-16" /></template>

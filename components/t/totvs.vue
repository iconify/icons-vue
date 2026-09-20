<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je6mkr0ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je6mkr0ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:totvs" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxw6x99ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rxw6x99ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:skull-rock-outline" /></template>

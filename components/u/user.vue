<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p69xj7f-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p69xj7f-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:user" /></template>

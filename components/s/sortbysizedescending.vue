<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru2pwbhep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="ru2pwbhep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sortbysizedescending" /></template>

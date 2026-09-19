<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozm9twbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ozm9twbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:meteor" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyte08niz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hyte08niz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:museum" /></template>

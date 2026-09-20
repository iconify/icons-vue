<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8a5w0b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t8a5w0b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:oil-well" /></template>

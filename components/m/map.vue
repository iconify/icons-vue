<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8y12nbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f8y12nbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:map" /></template>

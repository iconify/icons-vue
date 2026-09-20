<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-wdvunml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y-wdvunml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:meh-o" /></template>

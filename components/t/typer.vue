<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7_302kwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7_302kwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:typer" /></template>

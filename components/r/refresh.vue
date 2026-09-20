<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et4zv774r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="et4zv774r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:refresh" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag4uoqbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ag4uoqbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:paint-bucket-drop-16" /></template>

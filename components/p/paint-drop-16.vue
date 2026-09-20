<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgevnjv-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mgevnjv-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:paint-drop-16" /></template>

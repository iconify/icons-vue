<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdou5jn5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mdou5jn5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:paint-brush-thin-16" /></template>

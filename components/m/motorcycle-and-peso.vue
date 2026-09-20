<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf5fl2brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gf5fl2brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-and-peso" /></template>

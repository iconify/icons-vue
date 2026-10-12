<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4sk49bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c4sk49bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:moon-fill-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt7uuymsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nt7uuymsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:open-book-under-roof" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u09ol3bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="u09ol3bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:question" /></template>

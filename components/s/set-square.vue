<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo-zs0bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zo-zs0bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:set-square" /></template>

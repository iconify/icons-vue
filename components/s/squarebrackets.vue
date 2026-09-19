<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxkye7b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="oxkye7b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarebrackets" /></template>

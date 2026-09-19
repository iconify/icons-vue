<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg3ptdbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":662};
const content = `<path class="kg3ptdbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:paint" /></template>

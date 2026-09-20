<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw9aoy2ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xw9aoy2ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-inscription" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chto62blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="chto62blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-full" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxbstfbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bxbstfbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-x-thin" /></template>

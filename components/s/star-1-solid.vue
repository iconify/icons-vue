<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-5g7ib6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b-5g7ib6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:star-1-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxg9gvbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxg9gvbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:stack-exchange" /></template>

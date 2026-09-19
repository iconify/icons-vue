<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rey0q6hzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rey0q6hzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tree-filled" /></template>

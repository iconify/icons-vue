<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjcn9dsfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jjcn9dsfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:radio-unselected-filled" /></template>

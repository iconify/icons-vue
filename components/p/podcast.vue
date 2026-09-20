<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czri60elz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="czri60elz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:podcast" /></template>

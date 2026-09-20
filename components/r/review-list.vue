<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t32qhobhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t32qhobhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:review-list" /></template>

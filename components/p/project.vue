<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkjlr2bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bkjlr2bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:project" /></template>

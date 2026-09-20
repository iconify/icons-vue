<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-5ryxzgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k-5ryxzgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:sort-highest" /></template>

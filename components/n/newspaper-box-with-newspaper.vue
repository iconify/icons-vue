<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-2rxnbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i-2rxnbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:newspaper-box-with-newspaper" /></template>

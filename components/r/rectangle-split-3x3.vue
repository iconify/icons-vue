<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d73of2b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="d73of2b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-split-3x3" /></template>

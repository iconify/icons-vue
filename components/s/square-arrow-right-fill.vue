<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blh-a7_ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="blh-a7_ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-arrow-right-fill" /></template>

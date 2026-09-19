<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opdchxh-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="opdchxh-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:question-sign" /></template>

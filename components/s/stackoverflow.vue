<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by_na8eqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="by_na8eqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:stackoverflow" /></template>

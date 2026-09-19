<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq_93fakz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="lq_93fakz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:picasa" /></template>

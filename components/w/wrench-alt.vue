<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwg2n69-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jwg2n69-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:wrench-alt" /></template>

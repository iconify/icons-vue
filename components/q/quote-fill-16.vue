<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7jzx_b7q.css';
import '../../css/r/rx4fkk1gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m7jzx_b7q"/><path class="rx4fkk1gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:quote-fill-16" /></template>

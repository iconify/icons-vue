<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6u_pab5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="b6u_pab5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:x" /></template>

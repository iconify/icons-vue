<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-cdc3b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":895,"height":1024};
const content = `<path class="o-cdc3b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:psdown" /></template>

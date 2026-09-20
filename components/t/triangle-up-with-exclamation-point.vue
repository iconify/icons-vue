<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x16itb56c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x16itb56c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangle-up-with-exclamation-point" /></template>

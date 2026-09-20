<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo9hok72z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oo9hok72z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:shopping-jewels" /></template>

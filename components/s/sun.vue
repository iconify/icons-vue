<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9iraftnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b9iraftnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:sun" /></template>

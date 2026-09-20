<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmcnrkbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jmcnrkbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:transparency-grid" /></template>

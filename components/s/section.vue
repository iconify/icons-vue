<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6a5dms5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f6a5dms5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:section" /></template>

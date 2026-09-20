<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_h1qpsmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a_h1qpsmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:text-align-bottom" /></template>

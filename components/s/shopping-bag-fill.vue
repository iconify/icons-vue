<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-_m7sbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b-_m7sbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:shopping-bag-fill" /></template>

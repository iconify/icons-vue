<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnj8bkbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnj8bkbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mode" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7r7gl-bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7r7gl-bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:regex-filled" /></template>

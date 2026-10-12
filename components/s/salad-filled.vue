<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylo21vb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ylo21vb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:salad-filled" /></template>

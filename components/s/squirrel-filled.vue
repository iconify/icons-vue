<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw1k1qbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xw1k1qbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:squirrel-filled" /></template>

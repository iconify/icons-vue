<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgqe2rbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgqe2rbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-cloud-filled" /></template>

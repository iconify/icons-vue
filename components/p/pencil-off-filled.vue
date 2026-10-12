<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3bt1acyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3bt1acyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pencil-off-filled" /></template>

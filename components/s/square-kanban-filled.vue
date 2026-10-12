<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6x2anhby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r6x2anhby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-kanban-filled" /></template>

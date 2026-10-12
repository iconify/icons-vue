<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8v037b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8v037b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:table-properties-filled" /></template>

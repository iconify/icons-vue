<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng0jdeb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ng0jdeb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:search-check-filled" /></template>

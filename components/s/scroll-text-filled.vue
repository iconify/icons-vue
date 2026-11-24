<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4-d2ibnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4-d2ibnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scroll-text-filled" /></template>

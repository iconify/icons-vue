<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_6u22boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_6u22boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:text-search-filled" /></template>

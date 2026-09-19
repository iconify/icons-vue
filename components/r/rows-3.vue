<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjp272mmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjp272mmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rows-3" /></template>

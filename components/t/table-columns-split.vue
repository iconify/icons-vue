<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ide-xkj9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ide-xkj9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:table-columns-split" /></template>

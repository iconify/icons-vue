<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd6gj6bbb.css';
import '../../css/g/gdq0r_bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd6gj6bbb"/><path class="gdq0r_bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:search-big-plus" /></template>

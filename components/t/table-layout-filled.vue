<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we9t8-ysh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we9t8-ysh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:table-layout-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znt4nib0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znt4nib0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-reply" /></template>

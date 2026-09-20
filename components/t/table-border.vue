<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmgj_4bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmgj_4bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-border" /></template>

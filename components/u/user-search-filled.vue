<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdgv0f7nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdgv0f7nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-search-filled" /></template>

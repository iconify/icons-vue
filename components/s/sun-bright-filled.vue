<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-jooqg1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-jooqg1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sun-bright-filled" /></template>

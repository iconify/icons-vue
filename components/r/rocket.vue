<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxobl-b0u.css';
import '../../css/p/p42897ycd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxobl-b0u"/><path class="p42897ycd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rocket" /></template>

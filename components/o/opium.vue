<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6rrf8d9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p6rrf8d9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:opium" /></template>

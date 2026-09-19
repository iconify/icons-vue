<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu9bbcbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu9bbcbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:reader-comment" /></template>

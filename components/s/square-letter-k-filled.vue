<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urs5c65ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urs5c65ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-k-filled" /></template>

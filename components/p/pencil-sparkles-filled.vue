<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np0p-h43r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np0p-h43r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pencil-sparkles-filled" /></template>

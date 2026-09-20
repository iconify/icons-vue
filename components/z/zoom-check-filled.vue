<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trh51ymmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trh51ymmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zoom-check-filled" /></template>

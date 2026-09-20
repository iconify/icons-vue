<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps-6-ibio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps-6-ibio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:polygon" /></template>

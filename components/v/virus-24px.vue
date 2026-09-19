<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncnv5zbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ncnv5zbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:virus-24px" /></template>

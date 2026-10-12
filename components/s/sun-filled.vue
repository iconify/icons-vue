<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bev78jbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bev78jbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sun-filled" /></template>

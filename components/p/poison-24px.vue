<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8hbvbqty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w8hbvbqty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:poison-24px" /></template>

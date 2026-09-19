<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6_z9abcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6_z9abcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wine-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3zrck5ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3zrck5ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-pointer-click-filled" /></template>

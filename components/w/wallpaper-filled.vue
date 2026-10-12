<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey9534b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ey9534b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:wallpaper-filled" /></template>

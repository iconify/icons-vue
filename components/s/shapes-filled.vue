<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf6a-abur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf6a-abur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shapes-filled" /></template>

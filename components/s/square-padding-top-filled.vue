<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy0qvsn7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iy0qvsn7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-padding-top-filled" /></template>

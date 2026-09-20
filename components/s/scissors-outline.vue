<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g27w5fl7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g27w5fl7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scissors-outline" /></template>

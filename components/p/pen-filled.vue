<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l37b5fo4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l37b5fo4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pen-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4i-4cr0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4i-4cr0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:puzzle-filled" /></template>

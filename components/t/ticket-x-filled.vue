<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvyijfb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bvyijfb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ticket-x-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e08h97bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e08h97bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:popcorn-filled" /></template>

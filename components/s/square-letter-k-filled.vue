<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5209lwqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5209lwqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-k-filled" /></template>

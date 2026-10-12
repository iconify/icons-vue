<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7_paragx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b7_paragx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tool-case-filled" /></template>

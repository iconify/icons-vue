<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b00-xbc-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b00-xbc-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-h-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frgdqtr2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="frgdqtr2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-square-reply-filled" /></template>

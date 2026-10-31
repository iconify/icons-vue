<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9g45xbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s9g45xbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-chevrons-up-filled" /></template>

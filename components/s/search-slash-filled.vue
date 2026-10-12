<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df92hcbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="df92hcbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:search-slash-filled" /></template>

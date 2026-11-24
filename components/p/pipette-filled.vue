<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brkgtpbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="brkgtpbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pipette-filled" /></template>

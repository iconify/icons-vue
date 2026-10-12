<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py0upebda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="py0upebda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pocket-knife-filled" /></template>

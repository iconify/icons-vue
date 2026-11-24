<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-rl3m85n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l-rl3m85n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tube-lotion-filled" /></template>

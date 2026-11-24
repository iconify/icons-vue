<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fev3getav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fev3getav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:signpost-filled" /></template>

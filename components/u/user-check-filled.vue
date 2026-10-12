<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbce29bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbce29bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-check-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it8ye198a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it8ye198a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:whistle-filled" /></template>

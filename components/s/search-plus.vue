<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yahrr0snd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yahrr0snd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:search-plus" /></template>

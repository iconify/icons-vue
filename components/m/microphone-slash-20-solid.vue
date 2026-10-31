<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9ednac0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p9ednac0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:microphone-slash-20-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2_xb8b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2_xb8b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:phone-ringing-1-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmnto7zoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmnto7zoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-rounded-2-bold" /></template>

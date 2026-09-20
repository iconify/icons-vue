<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aii-ix-wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aii-ix-wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sticker-square-outline" /></template>

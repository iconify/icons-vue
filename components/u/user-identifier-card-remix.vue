<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgt_zxb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bgt_zxb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-identifier-card-remix" /></template>

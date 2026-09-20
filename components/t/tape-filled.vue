<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip199ph9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip199ph9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tape-filled" /></template>

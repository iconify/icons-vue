<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obtt7rbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obtt7rbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticker-remove" /></template>

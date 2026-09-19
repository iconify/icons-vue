<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph9khobot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph9khobot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:play" /></template>

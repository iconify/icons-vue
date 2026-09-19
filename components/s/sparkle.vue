<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu0w-vk1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu0w-vk1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sparkle" /></template>

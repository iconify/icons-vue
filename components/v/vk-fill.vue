<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlqn9tbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zlqn9tbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:vk-fill" /></template>

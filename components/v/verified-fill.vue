<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk4-p0bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vk4-p0bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:verified-fill" /></template>

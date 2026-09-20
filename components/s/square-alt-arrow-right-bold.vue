<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd6bosi-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nd6bosi-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-alt-arrow-right-bold" /></template>

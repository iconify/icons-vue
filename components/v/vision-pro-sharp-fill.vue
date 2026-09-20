<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chzbq8n6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="chzbq8n6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vision-pro-sharp-fill" /></template>

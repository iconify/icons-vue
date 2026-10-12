<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhs_bvkid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nhs_bvkid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-terminal-filled" /></template>

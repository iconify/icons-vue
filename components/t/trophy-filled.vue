<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go13jz64q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="go13jz64q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:trophy-filled" /></template>

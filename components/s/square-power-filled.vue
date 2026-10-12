<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1pf1jbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d1pf1jbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-power-filled" /></template>

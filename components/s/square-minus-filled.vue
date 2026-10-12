<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl64q8ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yl64q8ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-minus-filled" /></template>

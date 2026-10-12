<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5cu15grx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d5cu15grx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:paintbrush-filled" /></template>

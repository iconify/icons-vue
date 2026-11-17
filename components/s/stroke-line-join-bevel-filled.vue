<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd331cczw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xd331cczw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stroke-line-join-bevel-filled" /></template>

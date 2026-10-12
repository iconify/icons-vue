<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd3k9mbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xd3k9mbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rabbit-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq9-44b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq9-44b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-up-left-filled" /></template>

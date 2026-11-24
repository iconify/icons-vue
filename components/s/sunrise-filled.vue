<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phhuvpbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phhuvpbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sunrise-filled" /></template>

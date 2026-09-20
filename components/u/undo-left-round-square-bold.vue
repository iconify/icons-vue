<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx9oaobmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lx9oaobmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-left-round-square-bold" /></template>

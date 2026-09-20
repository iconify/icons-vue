<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr3bpp98z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lr3bpp98z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-cross-circle-bold" /></template>
